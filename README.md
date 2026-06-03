# Masoud Dehghani-Soufi — Academic Website

A free, self-contained personal academic website (single `index.html`).
No build tools, no frameworks, no cost — just upload and go.

## 🚀 Publish for free on GitHub Pages (≈5 minutes)

1. Create a free account at https://github.com
2. Click **New repository**. Name it **`<your-username>.github.io`**
   (e.g. `masoud-d.github.io`). Set it to **Public**.
3. Click **uploading an existing file** and drag in everything from this
   folder: `index.html`, `students.html`, the `assets/` folder, and the
   `materials/` folder.
4. Click **Commit changes**.
5. Go to **Settings → Pages**. Under *Branch*, choose `main` / `root` and
   **Save**.
6. Wait ~1 minute. Your site is live at **`https://<your-username>.github.io`**

That URL is permanent and free. Share it on your CV, LinkedIn, and email signature.

## ✏️ How to edit later

Everything is in `index.html`. Open it on GitHub (click the file → pencil icon)
and edit directly in the browser, then **Commit**. Changes go live in ~1 minute.

Look for the CAPITALISED comments to find each part, e.g.:
- `<!-- PUBLICATIONS -->` — copy one `<li>` to add a paper.
- `<!-- TIMELINE -->` — copy one `.tl-item` block to add a role.
- `<!-- RESEARCH CARDS -->` — copy a `.card` block to add a focus area.
- `<!-- COURSE MATERIALS TABLE -->` — copy a `<tr>` row to add a file.

## 📄 Updating your CV
Replace `assets/CV_Masoud_Dehghani-Soufi.pdf` with a newer file of the **same
name**. The "Download CV" buttons will then serve the new version automatically.

## 🖼️ Adding your photo
Drop a photo at `assets/profile.jpg`, then in `index.html` find the HERO section
and follow the comment to swap the placeholder initials for your image.

## 📚 Adding files / announcements for students
Student materials live on a **separate page: `students.html`** (linked from the
home page's Teaching section and the nav).
1. Put the file (PDF, slides, dataset…) into the `materials/` folder.
2. Open `students.html`, find `<!-- COURSE -->` or `<!-- FILE -->`, copy a block,
   and point the link to `materials/your-file.pdf`.
3. To post a new announcement, copy a `<div class="announce">` block (newest first).

## 🎨 Changing colours / fonts
Each page is self-contained. Edit the `:root` variables at the top of the
`<style>` block in `index.html` (and the same block in `students.html`).
Key variables: `--bg` (page background), `--forest` (dark green), and
`--accent` / `--accent-deep` (the teal highlight — change these to any colour,
e.g. a blue, to re-theme the whole site).

## 🗂️ File overview
- `index.html` — home (about, research, experience, publications, contact)
- `students.html` — dedicated student page (announcements, courses, materials)
- `assets/CV_Masoud_Dehghani-Soufi.pdf` — your downloadable CV
- `materials/` — course files students download

---
Built as a static site — works on any free host (GitHub Pages, Netlify, Cloudflare Pages).
