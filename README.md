# Villas for 2030 and beyond · Ankura Homes

A self-contained static website: the founders' brainstorm for a new villa community in Hyderabad, told in seven chapters (villa, community, landscape, amenities, budget, signature, outcomes), with the full research library underneath.

No build step. It is plain HTML, CSS and JavaScript; fonts load from Google Fonts.

## Deploy on GitHub Pages

1. Create a new repository on GitHub (for example `ankura-villas`).
2. Upload everything in this folder to the repository root, keeping the folders (`gallery/`, `plans/`, `refs/`, `match/`, `amen/`, `ebooks/`) and the `.nojekyll` file.
   - Easiest: on the repo page choose **Add file → Upload files**, drag the folder contents in, and commit. GitHub's web uploader takes up to 100 files at a time, so upload in two or three batches if needed.
   - Or with git:
     ```
     git init
     git add .
     git commit -m "Ankura villas site"
     git branch -M main
     git remote add origin https://github.com/<your-username>/ankura-villas.git
     git push -u origin main
     ```
3. In the repository go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, and save.
4. After a minute the site is live at `https://<your-username>.github.io/ankura-villas/`.

## Preview locally

Open `index.html` directly, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Notes

- The founders' deck is included as an offline PDF in `deck/`.
- Photos in `gallery/`, `match/` and `plans/` belong to the credited architects and photographers (see the evidence library). Keep the repository private or get permission before making it public.
- Prices and costs are indicative, from public asking prices and 2026 construction-rate guides.
