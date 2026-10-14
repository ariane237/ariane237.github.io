# Ariane Chrisko academic website

A static, responsive website for GitHub Pages. No installation or build step is needed.

## Files

- `index.html`: Home
- `research.html`: Research
- `publications.html`: Publications
- `teaching.html`: Teaching
- `style.css`: shared design and mobile layout
- `.nojekyll`: tells GitHub Pages to serve the files directly

## Publish on GitHub Pages

1. Create a public GitHub repository. Name it `YOUR-USERNAME.github.io` for a personal homepage, or choose any other name for a project website.
2. Extract the ZIP and upload its contents to the repository root. Upload the HTML files directly, rather than placing them inside another folder. Include `.nojekyll`.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)** and save.
5. GitHub will display your website address after deployment. A personal repository uses `https://YOUR-USERNAME.github.io/`; a project repository uses `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Before publishing

- Confirm all biography and teaching details.
- In `publications.html`, add the verified author lists, publication years, journal/status information and DOI or paper links. Titles alone are included to avoid asserting an unverified publication status.
- Add your preferred public professional email, ORCID, Google Scholar or institutional profile if desired. No personal email address is published in this starter.
- You can add a photograph and CV later. They are optional and there are no broken placeholder links.

## Edit or preview

Edit HTML text directly. For a local preview, open `index.html` in a browser or run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.
