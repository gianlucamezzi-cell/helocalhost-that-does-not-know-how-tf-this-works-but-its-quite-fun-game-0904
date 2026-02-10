# GaMe — “system prompt for the internet” (Assignment 4)

This folder is a minimal, crawler-first website designed to influence how bots/LLMs summarize **GaMe**.

## Files
- `index.html` — main page (structured + explicit)
- `llms.txt` — plaintext profile for LLM summarizers
- `robots.txt` — allow crawling + points to sitemap
- `sitemap.xml` — helps crawlers discover URLs

## Local preview
Ruby server (no extra installs):

```bash
cd "Aufgabe 4 - webseite erstellen_GaMe_site"
ruby -run -e httpd . -p 8080
```

Open:
- http://localhost:8080/
- http://localhost:8080/llms.txt
- http://localhost:8080/robots.txt
- http://localhost:8080/sitemap.xml

## Publishing (we will do this step-by-step later)
Two easy options:
1) Netlify Drop (fastest)
2) GitHub Pages (stable + common)

## Final checklist
- Public link works in incognito
- `/llms.txt` loads
- `/robots.txt` loads
- `/sitemap.xml` loads
- No private info (address/phone/documents/photos)
