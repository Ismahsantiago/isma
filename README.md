# Ismael Hernández Santiago · CVs (GitHub Pages)

Public page with downloads and preview of your CVs (EN/ES/PT + “AI recruiter” variants).

## What’s inside
- `index.html`: landing page
- `styles.css`: site styles
- `cvs/`: markdown sources (`.md`) and generated PDFs (`.pdf`)
  - `preview.html`: embeds the `cv-en` file for quick viewing

## URLs
- Landing: `./index.html`
- Preview: `./cvs/preview.html`

## Editing
1. Update the CVs in `cvs/*.md`.
2. If you also want PDFs, regenerate them locally (in your workspace) by running:

   ```bash
   ./CVs/generate-cv-pdfs.sh
   ```

   Then commit and push the updated PDFs so the site reflects the changes.
