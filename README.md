# Ismael Hernández Santiago · CVs (GitHub Pages)

Página pública con descargas y preview de tus CVs (EN/ES/PT + versiones “AI recruiter”).

## Contenido
- `index.html`: landing principal
- `styles.css`: estilos del sitio
- `cvs/`: markdowns (`.md`) y PDFs (`.pdf`)
  - `preview.html`: embebe `cv-en.pdf`

## URLs
- Landing: `./index.html`
- Preview: `./cvs/preview.html`

## Edición
1. Edita los CVs en `cvs/*.md`.
2. Regenera los PDFs **localmente** (en tu workspace) ejecutando:

   ```bash
   ./CVs/generate-cv-pdfs.sh
   ```

   Luego commitea y empuja los PDFs resultantes para que el sitio se actualice.
