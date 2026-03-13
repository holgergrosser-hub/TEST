# Netlify Frontend (statisch)

Diese Seite ist ein einfacher Einstiegspunkt mit:
- Link zum Termin (Calendly)
- Link zur Angebotsanfrage
- kleine FAQ-Suche aus `knowledge_base.json`

## Lokal testen

Öffne `frontend/index.html` im Browser (oder nutze einen lokalen Webserver).

## Netlify Deploy

- In Netlify: **New site from Git** → dieses Repo auswählen
- Build settings:
  - **Build command**: leer
  - **Publish directory**: `frontend`

Die Netlify-Konfiguration liegt in `netlify.toml`.
