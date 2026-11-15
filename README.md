# Zhenwei Zhang · Personal Homepage

Static academic homepage (single `index.html` + `profile.jpg`), no build step needed.

## Deploy to GitHub Pages
1. Create a public repository named exactly `<your-github-username>.github.io`.
2. Upload `index.html`, `profile.jpg` and this README to the repo root (GitHub web → "Add file → Upload files").
3. Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `(root)` → Save.
4. After ~1 minute the site is live at `https://<your-github-username>.github.io/`.

## Editing
- ResearchGate link: in `index.html`, search for `YOUR_PROFILE`, fill in your link and delete the `<!--` `-->` around them.
- News: add a new `<li>` at the top of the `#news` list.
- Publications: copy one `<li class="pub" data-c="j">` block; `data-c` = `j` (journal), `r` (under review), `c` (conference), `co` (co-authored).
- Replace `profile.jpg` with a higher-resolution photo if you have one (portrait, ~600×700 px).
